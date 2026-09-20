<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6olgfbfs.css';
import '../../css/c/cos-qwbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6olgfbfs"/><path class="cos-qwbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:messages-people-user-check-bold" /></template>
