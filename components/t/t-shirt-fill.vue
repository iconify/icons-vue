<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tehthnb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tehthnb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:t-shirt-fill" /></template>
