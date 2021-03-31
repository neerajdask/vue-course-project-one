<template>
  <ul>
    <li></li>
  </ul>
</template>

<script>
export default {
  data() {
    return {
      storedResources: [
        {
          id: 'official-guide',
          title: 'Official Guide',
          description: 'The official Vue.js documentation',
          link: 'https://vuejs.org',
        },
        {
          id: 'google',
          title: 'Google',
          description: 'Google your way out of trouble!',
          link: 'https://google.CO.IN',
        },
      ],
    };
  },
};
</script>