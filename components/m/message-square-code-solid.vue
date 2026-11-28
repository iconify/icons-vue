<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thz9ypb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thz9ypb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-code-solid" /></template>
