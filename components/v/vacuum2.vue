<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6hk6n6ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u6hk6n6ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:vacuum2" /></template>
