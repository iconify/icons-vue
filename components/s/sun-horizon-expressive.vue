<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buiy88btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="buiy88btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:sun-horizon-expressive" /></template>
