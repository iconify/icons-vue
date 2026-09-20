<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwqa2rb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwqa2rb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:passport-line" /></template>
