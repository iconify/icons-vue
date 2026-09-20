<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5o_dob7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5o_dob7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:volume-x" /></template>
