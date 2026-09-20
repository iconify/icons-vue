<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0lg2ebmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0lg2ebmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:server-bolt" /></template>
