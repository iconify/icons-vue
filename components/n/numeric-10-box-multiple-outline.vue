<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csnq9achd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csnq9achd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-10-box-multiple-outline" /></template>
