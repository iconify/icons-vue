<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcumr__tu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcumr__tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sun-off" /></template>
