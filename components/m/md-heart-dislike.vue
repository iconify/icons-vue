<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b85sq_bgw.css';
import '../../css/f/fzno83ceb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b85sq_bgw"/><path class="fzno83ceb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-heart-dislike" /></template>
