<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2a39z7-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2a39z7-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-chevron-up-sharp-fill" /></template>
