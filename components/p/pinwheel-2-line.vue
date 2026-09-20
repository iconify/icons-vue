<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc5qh5f2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc5qh5f2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pinwheel-2-line" /></template>
