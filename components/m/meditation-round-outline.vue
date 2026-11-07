<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le1pcms0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="le1pcms0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:meditation-round-outline" /></template>
