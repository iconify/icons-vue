<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmvjiybux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmvjiybux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:save-3-line" /></template>
