<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpnbucbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpnbucbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tree" /></template>
