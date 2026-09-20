<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-ds1qb9a.css';
import '../../css/m/m45_auk8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-ds1qb9a"/><path class="m45_auk8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:print-filled" /></template>
