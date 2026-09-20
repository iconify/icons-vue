<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og2u-rb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og2u-rb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-plus-outline" /></template>
