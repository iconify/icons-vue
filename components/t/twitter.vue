<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m581bqu3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m581bqu3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:twitter" /></template>
