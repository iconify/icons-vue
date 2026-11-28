<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfpk53bjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfpk53bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:thumbs-down-solid" /></template>
