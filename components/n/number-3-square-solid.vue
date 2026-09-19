<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whapzcc0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="whapzcc0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:number-3-square-solid" /></template>
