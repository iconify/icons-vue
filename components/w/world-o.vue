<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn0zm5bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn0zm5bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:world-o" /></template>
