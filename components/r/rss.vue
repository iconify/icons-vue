<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-_27iyyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-_27iyyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:rss" /></template>
