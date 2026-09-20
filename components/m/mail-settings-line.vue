<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s958x7bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s958x7bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mail-settings-line" /></template>
