<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv2_z3-bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv2_z3-bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-number-0-filled" /></template>
