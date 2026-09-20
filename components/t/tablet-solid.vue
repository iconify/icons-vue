<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-er0dsds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-er0dsds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:tablet-solid" /></template>
