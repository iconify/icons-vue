<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8htv1bid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k8htv1bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:taoism" /></template>
