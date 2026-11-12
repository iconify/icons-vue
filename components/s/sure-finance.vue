<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt6m2xbua.css';
import '../../css/u/u9cjpybxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pt6m2xbua"/><path class="u9cjpybxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sure-finance" /></template>
