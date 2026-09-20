<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9qs8prwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9qs8prwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:star-half-alt" /></template>
