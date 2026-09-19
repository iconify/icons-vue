<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnrq_6d0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnrq_6d0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:people-fill" /></template>
