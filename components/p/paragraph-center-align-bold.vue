<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gko5mnbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gko5mnbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:paragraph-center-align-bold" /></template>
