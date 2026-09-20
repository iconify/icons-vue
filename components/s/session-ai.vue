<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db_f8kbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="db_f8kbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:session-ai" /></template>
