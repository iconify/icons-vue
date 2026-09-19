<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_f_gsbag.css';
import '../../css/v/v22w14b1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_f_gsbag"/><path class="v22w14b1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:school-bus" /></template>
