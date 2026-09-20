<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkqbo8bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkqbo8bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pill-off" /></template>
