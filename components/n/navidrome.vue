<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/welyr_3mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="welyr_3mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:navidrome" /></template>
