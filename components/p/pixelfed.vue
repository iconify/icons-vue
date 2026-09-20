<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vybo6ujya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vybo6ujya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:pixelfed" /></template>
