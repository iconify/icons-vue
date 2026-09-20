<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndkix9b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndkix9b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:music-1-filled" /></template>
