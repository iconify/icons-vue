<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkygmcb8t.css';
import '../../css/a/ah052tbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkygmcb8t"/><path class="ah052tbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:medal-star-alt-filled" /></template>
