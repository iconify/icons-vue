<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oubbqxbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oubbqxbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:radio-btn-passive" /></template>
