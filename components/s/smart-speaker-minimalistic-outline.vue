<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zop31pd3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zop31pd3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smart-speaker-minimalistic-outline" /></template>
