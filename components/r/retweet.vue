<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy9r95yun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="cy9r95yun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:retweet" /></template>
