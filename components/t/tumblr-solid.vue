<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nch6exbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nch6exbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:tumblr-solid" /></template>
