<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffj6e6kvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ffj6e6kvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:widget6" /></template>
