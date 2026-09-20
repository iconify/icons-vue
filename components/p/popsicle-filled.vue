<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzrxujerd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzrxujerd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:popsicle-filled" /></template>
