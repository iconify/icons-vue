<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnjr0mc5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnjr0mc5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:video-sharp" /></template>
