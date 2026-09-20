<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7ftgt0ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x7ftgt0ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:stars4" /></template>
