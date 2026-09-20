<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi5qk-80e.css';
import '../../css/k/k2y623byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vi5qk-80e"/><path class="k2y623byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:zoom-fit-width-16" /></template>
