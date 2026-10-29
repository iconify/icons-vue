<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_qza1oqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_qza1oqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wallet-solid" /></template>
