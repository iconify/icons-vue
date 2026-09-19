<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5nmv_b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5nmv_b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:window-sensor" /></template>
