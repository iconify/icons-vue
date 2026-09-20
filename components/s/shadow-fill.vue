<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvf2m-bli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvf2m-bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shadow-fill" /></template>
