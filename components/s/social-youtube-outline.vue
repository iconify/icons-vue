<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjqs9ia_t.css';
import '../../css/p/pofkdk1ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cjqs9ia_t"/><path class="pofkdk1ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-youtube-outline" /></template>
