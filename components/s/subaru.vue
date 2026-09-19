<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_k4p1q0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_k4p1q0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:subaru" /></template>
