<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr7xbdwkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sr7xbdwkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:phone-off" /></template>
