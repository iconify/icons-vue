<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz-jg2hhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tz-jg2hhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-arrow-up-broken" /></template>
