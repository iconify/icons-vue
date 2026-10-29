<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu6wyi_ja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu6wyi_ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:passport-solid" /></template>
