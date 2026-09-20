<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxpe5mb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxpe5mb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:navigation-code" /></template>
