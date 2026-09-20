<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsk9izbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsk9izbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:paypal" /></template>
