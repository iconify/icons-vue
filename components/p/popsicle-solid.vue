<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec4by69ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ec4by69ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:popsicle-solid" /></template>
