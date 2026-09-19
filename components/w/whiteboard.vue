<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu32ykbtv.css';
import '../../css/a/aelxiub-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu32ykbtv"/><path class="aelxiub-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:whiteboard" /></template>
