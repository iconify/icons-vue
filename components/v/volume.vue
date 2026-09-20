<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw05-obst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw05-obst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:volume" /></template>
