<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr5ftn4xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr5ftn4xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:skateboard-off" /></template>
