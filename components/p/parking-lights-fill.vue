<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msyf_sb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msyf_sb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:parking-lights-fill" /></template>
