<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idkrwjqvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:takeout-dining-outline-sharp" /></template>
<style>
.idkrwjqvb {
  fill: currentColor;
  d: path("M7.8 18h8.412l.552-7.308H7.242zm-.63-8.308h9.667l.152-1.904L14.15 5h-4.3L7.012 7.789zm-.94.931L2.693 7.258l.65-.746L6.116 9.15l-.127-1.716L9.423 4h5.154l3.435 3.435l-.128 1.715l2.774-2.639l.65.747l-3.539 3.365zM6.874 19l-.642-8.377H17.77L17.127 19zm5.133-8.308");
}

</style>
