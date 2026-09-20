<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8re512mm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="a8re512mm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:panorama" /></template>
