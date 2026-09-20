<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tui_wvwks.css';
import '../../css/i/i7bd01w6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tui_wvwks"/><path class="i7bd01w6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:trophy" /></template>
