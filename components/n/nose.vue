<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnwdegbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qnwdegbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:nose" /></template>
