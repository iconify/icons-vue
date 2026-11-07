<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnuus6brx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnuus6brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-frame-2-broken" /></template>
