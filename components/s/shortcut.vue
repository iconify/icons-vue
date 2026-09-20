<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_pdndb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_pdndb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:shortcut" /></template>
