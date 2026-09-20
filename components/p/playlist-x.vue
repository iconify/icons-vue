<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yeie6zbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yeie6zbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:playlist-x" /></template>
