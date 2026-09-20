<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flmlmw7dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flmlmw7dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:octagon" /></template>
