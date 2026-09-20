<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa1ioi0ng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa1ioi0ng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:w3-logo-solid" /></template>
