<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrlezkb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrlezkb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:medusa" /></template>
