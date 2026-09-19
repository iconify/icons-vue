<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so7-n9bkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="so7-n9bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:truck" /></template>
