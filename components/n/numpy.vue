<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qslq46b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="qslq46b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:numpy" /></template>
