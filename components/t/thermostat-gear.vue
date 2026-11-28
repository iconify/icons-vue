<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/potmh-1wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="potmh-1wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:thermostat-gear" /></template>
