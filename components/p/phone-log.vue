<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybda85b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybda85b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:phone-log" /></template>
