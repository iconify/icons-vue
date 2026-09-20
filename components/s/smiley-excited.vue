<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_h8f4u0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_h8f4u0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smiley-excited" /></template>
