<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmnvvrb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:splitscreen-add-sharp" /></template>
<style>
.mmnvvrb1c {
  fill: currentColor;
  d: path("M4 10.635V4h16v6.635zM4 20v-6.615h16v1.042q-.17-.011-.315-.017q-.146-.006-.3-.025q-2.087 0-3.544 1.465t-1.457 3.535q0 .169.006.323t.018.292zm15 2.23V20h-2.23v-1H19v-2.23h1V19h2.23v1H20v2.23z");
}

</style>
