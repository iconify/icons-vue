<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwp-cymvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mwp-cymvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:praying-hands" /></template>
