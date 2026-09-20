<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q98nqjbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q98nqjbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:prometheus" /></template>
