<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1ot-4bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1ot-4bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:octane-render" /></template>
