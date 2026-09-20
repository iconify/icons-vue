<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-zu4_btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-zu4_btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:rectangle-vertical" /></template>
