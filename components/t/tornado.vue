<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn_cz7bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="tn_cz7bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:tornado" /></template>
