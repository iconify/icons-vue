<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfq1gi_xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfq1gi_xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-redial" /></template>
