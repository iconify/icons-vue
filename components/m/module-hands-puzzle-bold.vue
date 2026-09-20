<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdqrygb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdqrygb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:module-hands-puzzle-bold" /></template>
