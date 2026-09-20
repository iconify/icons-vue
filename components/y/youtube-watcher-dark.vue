<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szxsx5wma.css';
import '../../css/z/zf9qombco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="szxsx5wma"/><path class="zf9qombco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:youtube-watcher-dark" /></template>
