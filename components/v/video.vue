<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzcn2g39y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzcn2g39y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:video" /></template>
