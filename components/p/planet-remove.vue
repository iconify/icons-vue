<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbs16jbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbs16jbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:planet-remove" /></template>
