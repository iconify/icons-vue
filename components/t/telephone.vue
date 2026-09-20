<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n916_ac4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n916_ac4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:telephone" /></template>
