<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flvxn2zzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flvxn2zzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rewind-fill" /></template>
