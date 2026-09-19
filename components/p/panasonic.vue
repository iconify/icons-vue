<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nimb0073w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nimb0073w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:panasonic" /></template>
