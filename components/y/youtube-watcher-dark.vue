<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk6ey269v.css';
import '../../css/z/zf9qombco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sk6ey269v"/><path class="zf9qombco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:youtube-watcher-dark" /></template>
