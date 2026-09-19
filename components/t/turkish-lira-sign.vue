<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy_qmbbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="gy_qmbbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:turkish-lira-sign" /></template>
