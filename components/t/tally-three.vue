<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2rp9uikc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2rp9uikc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tally-three" /></template>
