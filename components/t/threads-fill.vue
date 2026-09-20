<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a56g3rbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a56g3rbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:threads-fill" /></template>
