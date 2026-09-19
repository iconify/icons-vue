<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfla51bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfla51bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:volume-up" /></template>
