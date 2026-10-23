<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myfzz2bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myfzz2bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:map-pin-minus-inside" /></template>
