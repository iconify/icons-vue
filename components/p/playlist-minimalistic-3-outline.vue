<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm3heybwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nm3heybwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-minimalistic-3-outline" /></template>
