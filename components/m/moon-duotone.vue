<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrqy14fcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrqy14fcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:moon-duotone" /></template>
