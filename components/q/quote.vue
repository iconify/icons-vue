<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6q6ugetu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":448};
const content = `<path class="n6q6ugetu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:quote" /></template>
