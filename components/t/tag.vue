<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h83a2chhh.css';
import '../../css/o/oncz_d6_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h83a2chhh"/><path class="oncz_d6_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:tag" /></template>
