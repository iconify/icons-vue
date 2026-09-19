<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l08bx5bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l08bx5bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:science-outlined" /></template>
