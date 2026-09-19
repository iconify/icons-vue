<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvy1shbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zvy1shbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:sound-min-solid" /></template>
