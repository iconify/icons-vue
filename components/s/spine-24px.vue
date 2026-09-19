<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo0pk69oh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo0pk69oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:spine-24px" /></template>
