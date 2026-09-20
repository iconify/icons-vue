<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp5uv_k8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sp5uv_k8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:stool" /></template>
