<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spqk0abml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spqk0abml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:send-ins-line" /></template>
