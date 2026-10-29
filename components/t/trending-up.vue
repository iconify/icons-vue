<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/binil8b-i.css';
import '../../css/q/qv-bz92zv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="binil8b-i"/><path class="qv-bz92zv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:trending-up" /></template>
