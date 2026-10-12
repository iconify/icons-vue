<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd3tyqb5z.css';
import '../../css/q/qskiz0blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd3tyqb5z"/><path class="qskiz0blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:spline-pointer-filled" /></template>
