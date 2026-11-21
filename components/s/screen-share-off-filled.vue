<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv72ichwa.css';
import '../../css/r/r14-wv_-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv72ichwa"/><path class="r14-wv_-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:screen-share-off-filled" /></template>
