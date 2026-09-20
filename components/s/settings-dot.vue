<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4bmz-b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4bmz-b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:settings-dot" /></template>
