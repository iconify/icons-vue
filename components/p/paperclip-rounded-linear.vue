<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqben4olh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqben4olh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paperclip-rounded-linear" /></template>
