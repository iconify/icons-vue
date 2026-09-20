<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5i_dnlrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i5i_dnlrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sim2" /></template>
