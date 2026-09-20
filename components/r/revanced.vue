<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dus1nvzmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dus1nvzmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:revanced" /></template>
