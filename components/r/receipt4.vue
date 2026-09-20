<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3cdjhwrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3cdjhwrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:receipt4" /></template>
