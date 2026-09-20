<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uei-4db6u.css';
import '../../css/u/u1hfyvlab.css';
import '../../css/w/w32_xebgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uei-4db6u"/><path clip-rule="evenodd" class="u1hfyvlab"/><path class="w32_xebgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openhands" /></template>
