<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swmyklbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swmyklbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ptu" /></template>
