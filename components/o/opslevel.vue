<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtvukff6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtvukff6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:opslevel" /></template>
