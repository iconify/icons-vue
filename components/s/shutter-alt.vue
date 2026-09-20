<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh9e62b2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh9e62b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:shutter-alt" /></template>
