<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yakqyacco.css';
import '../../css/l/lc21qzuqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yakqyacco"/><path class="lc21qzuqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-rounded-bold" /></template>
