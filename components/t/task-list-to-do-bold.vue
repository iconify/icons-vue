<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-uvrnlra.css';
import '../../css/b/b81tpq8nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-uvrnlra"/><path class="b81tpq8nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:task-list-to-do-bold" /></template>
