<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkc7o9b-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hkc7o9b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrows-left" /></template>
