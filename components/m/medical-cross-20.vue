<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx32cnbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tx32cnbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:medical-cross-20" /></template>
