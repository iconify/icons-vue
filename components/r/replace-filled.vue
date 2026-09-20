<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1a2x8b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1a2x8b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:replace-filled" /></template>
