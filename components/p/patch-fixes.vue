<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwylracsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwylracsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:patch-fixes" /></template>
