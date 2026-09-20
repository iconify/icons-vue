<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-ivx_rnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-ivx_rnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:meta" /></template>
