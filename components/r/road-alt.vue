<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7pve-3mm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7pve-3mm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:road-alt" /></template>
