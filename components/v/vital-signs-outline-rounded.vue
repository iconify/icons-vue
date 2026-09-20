<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvzrrjbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vital-signs-outline-rounded" /></template>
<style>
.gvzrrjbqb {
  fill: currentColor;
  d: path("M8.15 19.725q-.375-.275-.55-.7L5.3 13H2q-.425 0-.712-.288T1 12t.288-.712T2 11h4q.325 0 .563.175t.362.475L9 17.1l4.6-12.125q.175-.425.55-.7T15 4t.85.275t.55.7L18.7 11H22q.425 0 .713.288T23 12t-.288.713T22 13h-4q-.325 0-.562-.175t-.363-.475L15 6.9l-4.6 12.125q-.175.425-.55.7T9 20t-.85-.275");
}

</style>
