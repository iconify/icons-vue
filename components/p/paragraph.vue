<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmq_ozbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bmq_ozbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:paragraph" /></template>
