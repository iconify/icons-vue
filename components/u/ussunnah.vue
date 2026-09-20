<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aij4m_rjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aij4m_rjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:ussunnah" /></template>
