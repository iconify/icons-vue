<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1vgwybnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1vgwybnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:phone-outgoing-solid" /></template>
