<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltw3g9bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltw3g9bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:scan-traces" /></template>
