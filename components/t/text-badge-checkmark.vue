<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4x30vbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="g4x30vbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:text-badge-checkmark" /></template>
