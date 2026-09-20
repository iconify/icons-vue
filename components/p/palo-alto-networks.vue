<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv53gcbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv53gcbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:palo-alto-networks" /></template>
