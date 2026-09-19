<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu04n28xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vu04n28xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:skype" /></template>
