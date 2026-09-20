<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptdc-9sck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ptdc-9sck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-alt-arrow-left-outline" /></template>
