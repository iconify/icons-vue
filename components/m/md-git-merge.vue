<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzf2spbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bzf2spbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-git-merge" /></template>
