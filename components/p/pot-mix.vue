<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uox0lkpfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uox0lkpfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pot-mix" /></template>
