<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgpn75uou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgpn75uou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:wifi-check" /></template>
