<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw3qqeyqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw3qqeyqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:recycle-off" /></template>
