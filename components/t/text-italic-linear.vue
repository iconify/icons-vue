<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8jiy9bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8jiy9bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-italic-linear" /></template>
