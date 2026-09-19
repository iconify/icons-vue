<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl6zy2brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl6zy2brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:move-solid" /></template>
