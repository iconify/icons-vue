<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uidk0bb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uidk0bb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:scale-down" /></template>
