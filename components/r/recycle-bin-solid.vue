<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd0vk9vgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pd0vk9vgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:recycle-bin-solid" /></template>
