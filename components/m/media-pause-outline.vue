<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n86eppbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n86eppbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:media-pause-outline" /></template>
