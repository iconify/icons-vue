<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn1n6ybcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn1n6ybcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:maximize" /></template>
