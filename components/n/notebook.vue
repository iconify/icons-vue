<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzm3jzvqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzm3jzvqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:notebook" /></template>
