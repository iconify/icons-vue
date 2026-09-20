<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgnbqyb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:temperature-degree-celsius-24-regular" /></template>
<style>
.vgnbqyb0v {
  fill: currentColor;
  d: path("M4 8a1.5 1.5 0 1 1 3 0a1.5 1.5 0 0 1-3 0m1.5-3a3 3 0 1 0 0 6a3 3 0 0 0 0-6m6.847 2.875C11.543 8.775 11 10.146 11 12s.543 3.226 1.347 4.125c.8.895 1.906 1.375 3.153 1.375s2.353-.48 3.153-1.375c.282-.315.532-.688.737-1.12c.141-.296.429-.505.757-.505c.515 0 .89.495.682.966a6.3 6.3 0 0 1-1.058 1.659C18.671 18.355 17.152 19 15.5 19s-3.172-.645-4.271-1.875C10.133 15.899 9.5 14.146 9.5 12s.633-3.9 1.729-5.125C12.329 5.645 13.848 5 15.5 5s3.172.645 4.271 1.875a6.3 6.3 0 0 1 1.058 1.658c.207.472-.167.967-.682.967c-.328 0-.616-.208-.757-.505a4.7 4.7 0 0 0-.737-1.12C17.853 6.98 16.747 6.5 15.5 6.5s-2.353.48-3.153 1.375");
}

</style>
