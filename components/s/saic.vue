<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsk65cbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsk65cbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:saic" /></template>
