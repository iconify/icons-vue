<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbpnb1b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbpnb1b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:rows-2-plus-bottom" /></template>
