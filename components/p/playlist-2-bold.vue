<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb-pm1l6d.css';
import '../../css/e/ex199jb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb-pm1l6d"/><path clip-rule="evenodd" class="ex199jb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-2-bold" /></template>
