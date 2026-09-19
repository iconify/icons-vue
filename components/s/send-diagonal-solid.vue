<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yad_asbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yad_asbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:send-diagonal-solid" /></template>
