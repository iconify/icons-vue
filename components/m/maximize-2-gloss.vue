<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0iyle_8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0iyle_8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:maximize-2-gloss" /></template>
