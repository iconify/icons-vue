<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-715-84a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-715-84a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:watering-pot" /></template>
