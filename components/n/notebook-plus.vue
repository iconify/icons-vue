<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbrqlhbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbrqlhbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:notebook-plus" /></template>
