<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r29f78hcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r29f78hcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:roman-numeral-9" /></template>
