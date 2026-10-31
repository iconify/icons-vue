<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8b3c1bgc.css';
import '../../css/m/md2v-t2ws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="d8b3c1bgc"/><path class="md2v-t2ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:norfolk-island" /></template>
