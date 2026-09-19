<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhttcpb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bhttcpb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:microphone" /></template>
