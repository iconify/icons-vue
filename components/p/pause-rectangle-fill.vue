<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oefdycc4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="oefdycc4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:pause-rectangle-fill" /></template>
