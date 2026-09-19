<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x84cco1-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x84cco1-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nest-hub" /></template>
