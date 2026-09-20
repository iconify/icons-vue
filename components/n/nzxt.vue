<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myr7cwtvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myr7cwtvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nzxt" /></template>
