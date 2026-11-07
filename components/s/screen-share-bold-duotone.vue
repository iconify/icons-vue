<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aof5xebnh.css';
import '../../css/i/i2cm9bb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aof5xebnh"/><path clip-rule="evenodd" class="i2cm9bb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:screen-share-bold-duotone" /></template>
