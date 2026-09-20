<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi81_1wwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi81_1wwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:minutemailer" /></template>
