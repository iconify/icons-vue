<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfjgrpbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfjgrpbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-list-fill-round" /></template>
