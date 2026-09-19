<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw5iv4tez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cw5iv4tez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:server-fault" /></template>
