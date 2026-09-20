<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg78mjbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg78mjbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:ninja" /></template>
