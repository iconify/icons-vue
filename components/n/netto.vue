<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drxa8yvrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drxa8yvrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:netto" /></template>
