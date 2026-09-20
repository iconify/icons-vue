<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylib_ubbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ylib_ubbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-u-turn-left-sharp-fill" /></template>
