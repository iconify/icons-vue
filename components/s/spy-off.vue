<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcrt57btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcrt57btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:spy-off" /></template>
