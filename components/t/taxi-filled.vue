<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc1vbacqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc1vbacqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:taxi-filled" /></template>
