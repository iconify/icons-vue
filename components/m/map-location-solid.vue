<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7dtnxsic.css';
import '../../css/s/sega__bro.css';
import '../../css/v/vmfvg5bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7dtnxsic"/><path clip-rule="evenodd" class="sega__bro"/><path class="vmfvg5bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:map-location-solid" /></template>
