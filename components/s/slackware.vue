<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udw1abunk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udw1abunk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:slackware" /></template>
