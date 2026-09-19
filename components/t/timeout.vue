<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orzt67brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orzt67brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:timeout" /></template>
