<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-752u0ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-752u0ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:quote" /></template>
