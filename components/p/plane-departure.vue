<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmkr0povj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmkr0povj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:plane-departure" /></template>
