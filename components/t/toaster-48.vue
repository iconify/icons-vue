<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7sb8tbhe.css';
import '../../css/v/vj9dlzbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g7sb8tbhe"/><path class="vj9dlzbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:toaster-48" /></template>
