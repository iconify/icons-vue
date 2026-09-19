<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzmae1v_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uzmae1v_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:subscript2" /></template>
