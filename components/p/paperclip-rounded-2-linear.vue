<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1phvccex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1phvccex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paperclip-rounded-2-linear" /></template>
