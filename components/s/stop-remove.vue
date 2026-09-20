<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-998gbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-998gbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stop-remove" /></template>
