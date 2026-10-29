<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo4cnk_9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo4cnk_9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:play" /></template>
