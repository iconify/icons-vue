<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8b1vfbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u8b1vfbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:signpost-outline" /></template>
