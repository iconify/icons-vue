<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjk99yo8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjk99yo8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:soundcloud" /></template>
