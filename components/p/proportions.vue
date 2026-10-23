<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h78n5_b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h78n5_b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:proportions" /></template>
