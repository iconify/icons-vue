<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3-wgeheh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3-wgeheh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:zelle" /></template>
