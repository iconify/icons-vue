<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvwoswbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvwoswbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:recycle-variant" /></template>
