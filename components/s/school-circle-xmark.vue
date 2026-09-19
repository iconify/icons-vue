<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfku9-bda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="xfku9-bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:school-circle-xmark" /></template>
