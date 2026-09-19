<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w56591bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w56591bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:password-xmark" /></template>
