<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mns4sqbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mns4sqbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:plus-box" /></template>
