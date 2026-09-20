<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ics67bbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1545,"height":1151};
const content = `<path class="ics67bbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:onex" /></template>
