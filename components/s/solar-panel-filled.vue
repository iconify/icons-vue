<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqz6vo-oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqz6vo-oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:solar-panel-filled" /></template>
