<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1vsmrbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":4};
const content = `<path class="x1vsmrbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:range" /></template>
