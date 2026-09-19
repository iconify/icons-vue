<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdqo3k3dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdqo3k3dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:piano-grand-filled" /></template>
