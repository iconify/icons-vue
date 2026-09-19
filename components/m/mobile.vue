<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axdu2ub5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axdu2ub5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:mobile" /></template>
