<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocjh6qbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocjh6qbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:state" /></template>
