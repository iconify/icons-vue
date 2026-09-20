<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-j9djbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-j9djbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-chevron-up-filled" /></template>
