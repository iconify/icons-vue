<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0ck2zo1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0ck2zo1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:subtract" /></template>
