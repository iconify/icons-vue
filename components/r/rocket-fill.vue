<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wntamsb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wntamsb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rocket-fill" /></template>
