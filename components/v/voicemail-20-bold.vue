<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czj819b3o.css';
import '../../css/l/lh6vhf69p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="czj819b3o"/><path class="lh6vhf69p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voicemail-20-bold" /></template>
