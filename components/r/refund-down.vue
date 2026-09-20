<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myj2pl2-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myj2pl2-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:refund-down" /></template>
