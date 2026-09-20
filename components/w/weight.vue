<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd5613bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:weight" /></template>
<style>
.hd5613bif {
  fill: currentColor;
  d: path("M12 8q.425 0 .713-.288T13 7t-.288-.712T12 6t-.712.288T11 7t.288.713T12 8m1.71 0h2.346q.615 0 1.06.394q.444.394.53 1.004l1.252 8.77q.106.726-.376 1.279q-.481.553-1.233.553H6.711q-.752 0-1.234-.553t-.376-1.28l1.252-8.769q.087-.61.53-1.004Q7.33 8 7.945 8h2.347q-.133-.212-.212-.468Q10 7.275 10 7q0-.846.577-1.423T12 5t1.423.577T14 7q0 .275-.079.532q-.079.256-.211.468");
}

</style>
