<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag0ok82cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag0ok82cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:ungroup" /></template>
