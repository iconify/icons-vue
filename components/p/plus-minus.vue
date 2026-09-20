<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peuns4bme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="peuns4bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:plus-minus" /></template>
