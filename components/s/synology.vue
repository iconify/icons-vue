<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak0bvlpdn.css';
import '../../css/k/k8lgery7w.css';
import '../../css/z/zixffebzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ak0bvlpdn"/><path class="k8lgery7w"/><path class="zixffebzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:synology" /></template>
