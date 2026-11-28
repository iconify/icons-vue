<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6c3c4-rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6c3c4-rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:school-clock" /></template>
