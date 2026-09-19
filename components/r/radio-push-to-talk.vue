<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/penxt_bky.css';
import '../../css/r/rdotspt7s.css';
import '../../css/r/rbk3mibcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="penxt_bky"/><circle class="rdotspt7s"/><path class="rbk3mibcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:radio-push-to-talk" /></template>
