<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5z-95bkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5z-95bkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:swiggy" /></template>
