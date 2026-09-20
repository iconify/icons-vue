<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad1sq0als.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad1sq0als"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:phone-paused-line" /></template>
