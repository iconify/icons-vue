<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz6wdbc0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz6wdbc0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:passport-alert" /></template>
