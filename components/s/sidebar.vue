<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izpv9_ypd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izpv9_ypd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sidebar" /></template>
