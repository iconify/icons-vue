<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8xjw20cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8xjw20cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scissors" /></template>
