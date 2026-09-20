<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv9lud5-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv9lud5-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:thunderbird" /></template>
