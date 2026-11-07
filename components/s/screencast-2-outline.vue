<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5qai0b8i.css';
import '../../css/z/zpnr2hbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5qai0b8i"/><path clip-rule="evenodd" class="zpnr2hbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:screencast-2-outline" /></template>
