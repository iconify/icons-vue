<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txvb3pb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1070,"height":1000};
const content = `<path class="txvb3pb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:user" /></template>
