<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf-a91bde.css';
import '../../css/q/q0zx9pbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xf-a91bde"/><path class="q0zx9pbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifer-bold" /></template>
