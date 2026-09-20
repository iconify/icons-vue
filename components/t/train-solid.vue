<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3bwjxbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3bwjxbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:train-solid" /></template>
