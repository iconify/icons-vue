<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scufdzb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scufdzb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:video-call-check" /></template>
