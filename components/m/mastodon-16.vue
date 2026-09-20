<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsallabfa.css';
import '../../css/h/hc04_ac_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xsallabfa"/><path clip-rule="evenodd" class="hc04_ac_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:mastodon-16" /></template>
