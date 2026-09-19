<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh0647bhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh0647bhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:sunrise" /></template>
