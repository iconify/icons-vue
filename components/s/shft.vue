<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcujsn75d.css';
import '../../css/a/a3rqikbuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcujsn75d"/><path class="a3rqikbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:shft" /></template>
