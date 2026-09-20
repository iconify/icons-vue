<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2rgp6b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:notifications-unread" /></template>
<style>
.x2rgp6b8a {
  fill: currentColor;
  d: path("M11.997 21.385q-.668 0-1.14-.475q-.472-.474-.472-1.14h3.23q0 .67-.475 1.143q-.476.472-1.143.472M5 18.769v-1h1.616V9.846q0-1.96 1.24-3.447T11 4.546V4q0-.417.291-.708q.291-.292.707-.292t.709.292T13 4v.075q-.442.616-.683 1.342q-.24.727-.24 1.487q0 1.998 1.395 3.422t3.374 1.463h.27q.134 0 .268-.02v6H19v1zM15.192 8.675q-.73-.728-.73-1.769t.728-1.772t1.77-.73t1.77.728t.732 1.77t-.729 1.771t-1.77.73t-1.77-.728");
}

</style>
