<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gee7l6brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gee7l6brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:phone-pen-2" /></template>
