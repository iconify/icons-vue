<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzkpf5bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yzkpf5bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-back-outline" /></template>
