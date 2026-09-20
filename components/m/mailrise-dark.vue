<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2ds99bls.css';
import '../../css/y/yurlis35z.css';
import '../../css/b/b93z67b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v2ds99bls"/><path class="yurlis35z"/><path class="b93z67b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailrise-dark" /></template>
