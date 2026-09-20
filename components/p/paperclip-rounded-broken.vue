<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-kz5nbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-kz5nbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paperclip-rounded-broken" /></template>
