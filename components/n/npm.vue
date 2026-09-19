<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ootz-9bss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ootz-9bss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:npm" /></template>
