<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bri9ce21d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bri9ce21d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:taiwan-dollar" /></template>
