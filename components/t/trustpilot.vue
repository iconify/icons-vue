<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0216bb9l.css';
import '../../css/o/o_a2tub4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0216bb9l"/><path class="o_a2tub4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:trustpilot" /></template>
