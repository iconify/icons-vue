<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxy7l51_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxy7l51_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:sap" /></template>
