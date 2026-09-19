<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plwpeyfet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plwpeyfet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:triple-wall-switch" /></template>
