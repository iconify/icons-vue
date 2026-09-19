<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prai_vbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="prai_vbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:screwdriveralt" /></template>
