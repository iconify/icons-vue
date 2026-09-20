<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdkomdvjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdkomdvjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:roller-shade-closed" /></template>
