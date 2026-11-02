<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8nz2m9bq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8nz2m9bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:volume-off-line" /></template>
