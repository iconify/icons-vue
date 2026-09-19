<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpjhhactr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gpjhhactr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:number-circle-fill" /></template>
