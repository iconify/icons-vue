<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzjen9jeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzjen9jeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:service" /></template>
