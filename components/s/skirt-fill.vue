<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnxv5rusv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnxv5rusv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:skirt-fill" /></template>
