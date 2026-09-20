<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj92gibpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj92gibpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-off-outline" /></template>
