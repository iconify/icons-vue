<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw53pfbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw53pfbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:paragraph" /></template>
