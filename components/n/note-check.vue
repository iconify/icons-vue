<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvv9qhw4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvv9qhw4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:note-check" /></template>
