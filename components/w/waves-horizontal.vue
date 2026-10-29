<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl840eg2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl840eg2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:waves-horizontal" /></template>
