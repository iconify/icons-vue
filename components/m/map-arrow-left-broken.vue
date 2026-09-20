<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl2lyq-gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl2lyq-gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-arrow-left-broken" /></template>
