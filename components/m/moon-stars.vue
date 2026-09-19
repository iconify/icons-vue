<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-t034vxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-t034vxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:moon-stars" /></template>
