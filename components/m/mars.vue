<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg2wotpyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sg2wotpyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mars" /></template>
