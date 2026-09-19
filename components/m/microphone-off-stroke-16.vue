<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7c9z5_wq.css';
import '../../css/k/kmcbvkrhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b7c9z5_wq"/><path class="kmcbvkrhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:microphone-off-stroke-16" /></template>
