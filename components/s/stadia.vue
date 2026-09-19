<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qckhk8bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qckhk8bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:stadia" /></template>
