<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0g79acrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r0g79acrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smart-speaker-outline" /></template>
