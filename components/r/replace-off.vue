<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdnyquupd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdnyquupd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:replace-off" /></template>
