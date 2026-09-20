<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6i3jx7ty.css';
import '../../css/c/c88l3cbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6i3jx7ty"/><path class="c88l3cbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:moon-rising-filled" /></template>
