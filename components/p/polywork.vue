<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grcw_sb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grcw_sb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:polywork" /></template>
