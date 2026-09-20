<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4tztr9dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4tztr9dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:more-muted-horiz-line" /></template>
