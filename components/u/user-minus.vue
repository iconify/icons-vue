<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkpyemazk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkpyemazk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:user-minus" /></template>
