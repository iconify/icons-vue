<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts2o_1x0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts2o_1x0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mouse" /></template>
