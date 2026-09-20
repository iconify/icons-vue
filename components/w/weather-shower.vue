<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwb7nl58g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwb7nl58g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:weather-shower" /></template>
