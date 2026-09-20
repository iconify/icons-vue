<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z213nxxba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z213nxxba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ray-end-arrow" /></template>
