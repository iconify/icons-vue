<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt_keepgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt_keepgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wall-flood" /></template>
