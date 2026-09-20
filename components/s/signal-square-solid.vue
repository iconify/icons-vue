<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwlnpxbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwlnpxbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:signal-square-solid" /></template>
