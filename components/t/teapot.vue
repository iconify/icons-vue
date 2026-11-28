<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlwdbmc7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlwdbmc7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:teapot" /></template>
