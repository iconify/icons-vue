<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_pimdbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_pimdbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:message-01" /></template>
