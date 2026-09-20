<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk-jv5d0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk-jv5d0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:money-dollar-box-fill" /></template>
