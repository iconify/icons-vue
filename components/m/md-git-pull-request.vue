<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkovc3a7g.css';
import '../../css/e/egti8_jds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tkovc3a7g"/><path class="egti8_jds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-git-pull-request" /></template>
