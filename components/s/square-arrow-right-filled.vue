<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2p852bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2p852bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-arrow-right-filled" /></template>
