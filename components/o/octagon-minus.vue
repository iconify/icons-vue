<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv3tyz5ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv3tyz5ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:octagon-minus" /></template>
