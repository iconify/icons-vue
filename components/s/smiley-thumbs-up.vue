<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx2nxk0bk.css';
import '../../css/n/ndzomeb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx2nxk0bk"/><path class="ndzomeb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:smiley-thumbs-up" /></template>
