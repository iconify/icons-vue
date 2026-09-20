<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye-7s2bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye-7s2bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:okx" /></template>
