<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1iss4-fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1iss4-fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wineglass-triangle-broken" /></template>
