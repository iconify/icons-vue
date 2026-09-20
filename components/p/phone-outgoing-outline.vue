<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a932mxspb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a932mxspb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-outgoing-outline" /></template>
