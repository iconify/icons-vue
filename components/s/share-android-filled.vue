<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw3taiytu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw3taiytu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:share-android-filled" /></template>
