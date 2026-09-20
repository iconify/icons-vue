<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7jr9s6ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7jr9s6ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:map-check" /></template>
