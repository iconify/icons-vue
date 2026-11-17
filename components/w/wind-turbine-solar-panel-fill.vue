<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urhmm4mdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wind-turbine-solar-panel-fill" /></template>
<style>
.urhmm4mdx {
  fill: currentColor;
  d: path("m8.932 6.483l2.191.586a1 1 0 0 1 .401 1.717c-1.001.879-2.324.898-3.524.48V21a1 1 0 0 1-2 0V9.414l-1.121 1.122a1.002 1.002 0 0 1-1.688-.511c-.318-1.592.692-2.902 1.943-3.745c.1-.26.255-.497.452-.694l-.587-2.191a.999.999 0 0 1 1.286-1.206c.747.253 1.319.77 1.7 1.454c.358.642.521 1.373.572 2.101c.174.216.303.47.375.739M15 12v4h-4.383l.391-3.124A1 1 0 0 1 12 12Zm2 4v-4h3a1 1 0 0 1 .992.876L21.383 16Zm-6.633 2H15v4h-4a1 1 0 0 1-.992-1.124ZM17 18h4.633l.359 2.876A.997.997 0 0 1 21 22h-4Z");
}

</style>
