<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu7er63ka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu7er63ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:ticket" /></template>
