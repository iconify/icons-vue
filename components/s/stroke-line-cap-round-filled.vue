<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo3ie7blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xo3ie7blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:stroke-line-cap-round-filled" /></template>
