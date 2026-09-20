<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj-ki2brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj-ki2brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:steering-2-line" /></template>
