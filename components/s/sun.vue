<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-q9jwbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-q9jwbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:sun" /></template>
