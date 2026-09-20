<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkj1g9zqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkj1g9zqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:servbay" /></template>
