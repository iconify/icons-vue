<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9ms0wllv.css';
import '../../css/d/dd6fl6u9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="z9ms0wllv"/><path class="dd6fl6u9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:volume-low" /></template>
