<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1_y72bar.css';
import '../../css/b/b-ei31biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n1_y72bar"/><path class="b-ei31biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-2-bold-duotone" /></template>
