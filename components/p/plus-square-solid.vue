<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpzczrkzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpzczrkzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:plus-square-solid" /></template>
