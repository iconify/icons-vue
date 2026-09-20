<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cujg5k7cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cujg5k7cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:map-down" /></template>
