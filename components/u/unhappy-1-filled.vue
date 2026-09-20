<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5ckxuoab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5ckxuoab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:unhappy-1-filled" /></template>
