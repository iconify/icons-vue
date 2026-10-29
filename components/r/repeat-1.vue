<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn2thbb_r.css';
import '../../css/p/pbr8cipxb.css';
import '../../css/c/cf7crkx6v.css';
import '../../css/u/udhws4j8w.css';
import '../../css/f/fs_353-hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn2thbb_r wm-k"/><path class="pbr8cipxb wm-k"/><path class="cf7crkx6v wm-a"/><path class="udhws4j8w wm-a"/><path class="fs_353-hf wm-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:repeat-1" /></template>
