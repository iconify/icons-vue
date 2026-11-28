<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elin9y5mw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elin9y5mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-key-solid" /></template>
