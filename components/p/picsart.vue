<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adqyh6bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adqyh6bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:picsart" /></template>
