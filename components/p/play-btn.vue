<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbx2edc6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xbx2edc6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:play-btn" /></template>
