<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg0betbhc.css';
import '../../css/d/ddgckv3ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kg0betbhc"/><rect class="ddgckv3ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:queue" /></template>
