<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaaagyarv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uaaagyarv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-7" /></template>
