<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymhmnonmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymhmnonmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:octagon-filled" /></template>
