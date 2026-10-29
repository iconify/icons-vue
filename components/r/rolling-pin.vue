<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi9tr3bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qi9tr3bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rolling-pin" /></template>
