<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp2qei.css';
import '../../css/s/so-from-66.css';
import '../../css/f/fill-to-1.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp2qei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:square-filled" /></template>
