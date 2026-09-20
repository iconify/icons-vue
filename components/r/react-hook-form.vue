<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qftch_bhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qftch_bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:react-hook-form" /></template>
