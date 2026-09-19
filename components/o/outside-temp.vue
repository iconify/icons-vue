<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv_birdit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv_birdit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:outside-temp" /></template>
