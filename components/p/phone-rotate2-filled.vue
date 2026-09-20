<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg-3l4cle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wg-3l4cle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:phone-rotate2-filled" /></template>
