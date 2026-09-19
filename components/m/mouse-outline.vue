<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw-jojnkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gw-jojnkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:mouse-outline" /></template>
