<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgl1-4xan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="cgl1-4xan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:sun-dust-fill" /></template>
