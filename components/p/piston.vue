<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmrb8ackn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mmrb8ackn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:piston" /></template>
