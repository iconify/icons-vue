<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmau_cbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmau_cbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:swisspost" /></template>
