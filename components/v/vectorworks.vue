<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br7fvbb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br7fvbb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:vectorworks" /></template>
