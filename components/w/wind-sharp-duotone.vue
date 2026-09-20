<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp7g2yimv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp7g2yimv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wind-sharp-duotone" /></template>
