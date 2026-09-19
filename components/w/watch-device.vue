<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztfwjikic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztfwjikic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:watch-device" /></template>
