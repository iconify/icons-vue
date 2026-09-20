<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcgmcfopp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="hcgmcfopp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:minus-small-solid" /></template>
