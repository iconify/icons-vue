<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lmbl6xb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pair-20-filled" /></template>
<style>
.lmbl6xb4h {
  fill: currentColor;
  d: path("M12.25 2A1.75 1.75 0 0 1 13 5.33V7h1.67A1.748 1.748 0 1 1 17 9.33v5.34A1.749 1.749 0 1 1 14.67 17H9.33A1.748 1.748 0 1 1 7 14.67V13H5.33A1.748 1.748 0 1 1 3 10.67V5.33A1.748 1.748 0 1 1 5.33 3h5.34c.282-.59.882-1 1.58-1m.75 8.67A1.749 1.749 0 1 1 10.67 13H8.5v1.67c.363.173.656.467.83.83h5.34c.174-.363.467-.657.83-.83V9.33a1.75 1.75 0 0 1-.83-.83H13zM5.33 4.5a1.75 1.75 0 0 1-.83.83v5.34c.363.173.656.467.83.83H7V9.33A1.748 1.748 0 1 1 9.33 7h2.17V5.33a1.75 1.75 0 0 1-.83-.83zm4 4a1.75 1.75 0 0 1-.83.83v2.17h2.17c.174-.363.467-.657.83-.83V8.5z");
}

</style>
