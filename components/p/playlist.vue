<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsljz7bgq.css';
import '../../css/b/bgbj2wc5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsljz7bgq"/><path class="bgbj2wc5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:playlist" /></template>
