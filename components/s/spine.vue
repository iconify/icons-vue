<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qria0dbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qria0dbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:spine" /></template>
