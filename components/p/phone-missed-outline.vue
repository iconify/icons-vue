<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j12mt-oug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j12mt-oug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-missed-outline" /></template>
