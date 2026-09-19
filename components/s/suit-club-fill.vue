<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w16kcwbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="w16kcwbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:suit-club-fill" /></template>
