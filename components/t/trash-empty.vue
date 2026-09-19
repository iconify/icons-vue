<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eavwb2bkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eavwb2bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:trash-empty" /></template>
