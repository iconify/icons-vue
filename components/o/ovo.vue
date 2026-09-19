<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owmzy3k6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owmzy3k6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ovo" /></template>
