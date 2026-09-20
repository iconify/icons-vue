<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdg_z8g7j.css';
import '../../css/m/m3bb8qa6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdg_z8g7j"/><path class="m3bb8qa6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:notion" /></template>
