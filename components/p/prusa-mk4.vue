<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4i4jqjrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4i4jqjrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:prusa-mk4" /></template>
