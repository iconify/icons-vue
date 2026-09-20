<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuax2_bog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuax2_bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:wifi-slash" /></template>
