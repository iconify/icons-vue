<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttyx4f7fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttyx4f7fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:textalign-center" /></template>
