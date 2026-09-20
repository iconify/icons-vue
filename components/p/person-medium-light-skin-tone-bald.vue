<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="lwokxbbfy"/><path class="dfc0bdbio"/><path class="jdbh6ab2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:person-medium-light-skin-tone-bald" /></template>
<style>
.dfc0bdbio {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M18 31c-2.347 0-3.575-1.16-3.707-1.293a.999.999 0 0 1 1.404-1.424c.051.047.806.717 2.303.717c1.519 0 2.273-.69 2.305-.719a1.01 1.01 0 0 1 1.408.029a.994.994 0 0 1-.006 1.397C21.575 29.84 20.347 31 18 31m1-5h-2a1 1 0 1 1 0-2h2a1 1 0 1 1 0 2");
}

.jdbh6ab2a {
  fill: var(--svg-color--662113, #662113);
  d: path("M13 22a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0v2a1 1 0 0 1-1 1m10 0a1 1 0 0 1-1-1v-2a1 1 0 1 1 2 0v2a1 1 0 0 1-1 1");
}

.lwokxbbfy {
  fill: var(--svg-color--f3d2a2, #f3d2a2);
  d: path("M29.5 15.886C28.406 8.197 23.392 4.761 18 4.761S7.594 8.197 6.5 15.886c-1.381 0-2.5 1.791-2.5 4c0 2.107 1.021 3.815 2.314 3.97c1.223 6.649 5.985 10.53 11.686 10.53s10.463-3.881 11.685-10.53c1.294-.155 2.315-1.863 2.315-3.97c0-2.209-1.119-4-2.5-4");
}

</style>
