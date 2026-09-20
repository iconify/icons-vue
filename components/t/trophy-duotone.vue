<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tui_wvwks.css';
import '../../css/h/h_xkxebgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tui_wvwks"/><path class="h_xkxebgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:trophy-duotone" /></template>
