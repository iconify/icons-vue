<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euzbedc8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="euzbedc8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:minimize-sharp-two-tone" /></template>
