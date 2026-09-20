<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo_thyb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo_thyb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:slash-diamond-solid" /></template>
