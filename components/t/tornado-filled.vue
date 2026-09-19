<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujb3xbcfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujb3xbcfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tornado-filled" /></template>
