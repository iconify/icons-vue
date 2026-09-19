<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as3krabjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="as3krabjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:ruler-horizontal" /></template>
