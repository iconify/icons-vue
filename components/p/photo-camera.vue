<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2q6xw-zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z2q6xw-zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:photo-camera" /></template>
