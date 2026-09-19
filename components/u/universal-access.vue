<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvdq9tbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="tvdq9tbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:universal-access" /></template>
