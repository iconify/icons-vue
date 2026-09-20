<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo96tyb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo96tyb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:network-error-fill" /></template>
