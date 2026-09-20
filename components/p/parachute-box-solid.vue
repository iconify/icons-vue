<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk7hu_bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kk7hu_bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:parachute-box-solid" /></template>
