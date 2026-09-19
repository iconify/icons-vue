<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma981cbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2016,"height":2176};
const content = `<path class="ma981cbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:shield-times" /></template>
