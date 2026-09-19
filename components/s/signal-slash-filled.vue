<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rctg5spaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rctg5spaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:signal-slash-filled" /></template>
