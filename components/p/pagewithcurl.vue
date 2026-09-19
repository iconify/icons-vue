<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzdetfb7j.css';
import '../../css/w/w8qy4b3yq.css';
import '../../css/r/r83kv-bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jzdetfb7j"/><path class="w8qy4b3yq"/><path class="r83kv-bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:pagewithcurl" /></template>
