<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frg1mobbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frg1mobbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:new-folder" /></template>
