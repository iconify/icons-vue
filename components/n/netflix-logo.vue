<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4y-mwcbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4y-mwcbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:netflix-logo" /></template>
