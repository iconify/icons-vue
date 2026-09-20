<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja0gh3bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ja0gh3bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rewind-sharp-fill" /></template>
