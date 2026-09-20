<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwr6g16yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwr6g16yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:servers" /></template>
