<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8wpxd25d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8wpxd25d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:question-solid" /></template>
