<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g87f5fb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g87f5fb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:skip-next-filled" /></template>
