<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lii6gfblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lii6gfblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:user-off-filled" /></template>
