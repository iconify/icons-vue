<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqpl8jb6z.css';
import '../../css/v/vamw6spgm.css';
import '../../css/j/j2l4c4iul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqpl8jb6z"/><path clip-rule="evenodd" class="vamw6spgm"/><path class="j2l4c4iul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:running-bold-duotone" /></template>
