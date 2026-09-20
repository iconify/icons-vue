<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2-eyvwcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2-eyvwcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:polygon" /></template>
