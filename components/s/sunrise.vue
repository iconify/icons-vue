<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu9cchatv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu9cchatv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:sunrise" /></template>
