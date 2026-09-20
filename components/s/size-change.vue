<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzji_4r5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzji_4r5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:size-change" /></template>
