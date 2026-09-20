<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo0bw59ba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wo0bw59ba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:tram-side" /></template>
