<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ico_k8sza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ico_k8sza wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:signpost-gloss" /></template>
