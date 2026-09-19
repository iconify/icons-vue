<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afa51_zkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afa51_zkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:vrt-radio1" /></template>
