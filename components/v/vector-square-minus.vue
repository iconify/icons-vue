<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b05s4wdea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b05s4wdea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-square-minus" /></template>
