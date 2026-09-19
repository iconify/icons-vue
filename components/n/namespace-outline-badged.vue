<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_yhajbgl.css';
import '../../css/y/yjfke8kwc.css';
import '../../css/l/lmf0ecbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="h_yhajbgl"/><path class="yjfke8kwc"/><circle class="lmf0ecbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:namespace-outline-badged" /></template>
