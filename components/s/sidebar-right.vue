<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcpscr_4z.css';
import '../../css/b/b6dzwabah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcpscr_4z"/><path class="b6dzwabah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sidebar-right" /></template>
