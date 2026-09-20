<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng8cxbbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng8cxbbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:thumb-up-1-filled" /></template>
