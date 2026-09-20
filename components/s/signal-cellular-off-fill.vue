<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lntwjhq8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lntwjhq8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:signal-cellular-off-fill" /></template>
