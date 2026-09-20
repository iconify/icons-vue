<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7s6gibfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7s6gibfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-chevrons-up-sharp-fill" /></template>
