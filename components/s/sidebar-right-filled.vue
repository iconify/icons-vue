<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0ac-ybds.css';
import '../../css/b/b6dzwabah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0ac-ybds"/><path class="b6dzwabah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sidebar-right-filled" /></template>
