<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4fn3vt9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z4fn3vt9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:phone-solid" /></template>
