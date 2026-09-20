<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixa2rjbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixa2rjbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:spatula-line" /></template>
