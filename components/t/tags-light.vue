<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8m_hmjin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="k8m_hmjin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:tags-light" /></template>
