<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9y3__bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9y3__bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:service-fill" /></template>
