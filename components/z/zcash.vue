<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6u-33gie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6u-33gie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zcash" /></template>
