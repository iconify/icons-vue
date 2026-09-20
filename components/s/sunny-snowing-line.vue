<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tced3cb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tced3cb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:sunny-snowing-line" /></template>
