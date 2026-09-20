<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd2psoywp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd2psoywp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:tvk" /></template>
