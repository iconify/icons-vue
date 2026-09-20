<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhl7gxb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qhl7gxb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:number" /></template>
