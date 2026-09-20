<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7f8u6bwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7f8u6bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:postmates" /></template>
