<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eog_x572l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eog_x572l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:noodle-filled" /></template>
