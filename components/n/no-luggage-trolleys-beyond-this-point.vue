<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt7k6rbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt7k6rbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-luggage-trolleys-beyond-this-point" /></template>
