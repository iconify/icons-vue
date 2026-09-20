<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8sb9kpfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8sb9kpfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:thumb-down-2-filled" /></template>
