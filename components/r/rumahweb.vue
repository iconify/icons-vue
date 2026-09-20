<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyjbf850m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyjbf850m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rumahweb" /></template>
