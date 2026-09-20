<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw-vemdnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw-vemdnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:radio-line" /></template>
