<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck52k8vxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck52k8vxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:replica" /></template>
