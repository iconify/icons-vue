<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh4odwcwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh4odwcwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:subtitleedit" /></template>
