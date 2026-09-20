<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_15ldbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_15ldbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:scale-unbalanced-solid" /></template>
