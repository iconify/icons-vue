<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnq13b_qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gnq13b_qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:triangle-lefthalf-fill" /></template>
