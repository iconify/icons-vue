<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djyc7gb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djyc7gb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:radical-sharp-duotone" /></template>
