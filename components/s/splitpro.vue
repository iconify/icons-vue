<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w03s3zj-z.css';
import '../../css/k/kc4mupbht.css';
import '../../css/h/hdwjuyb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w03s3zj-z"/><path class="kc4mupbht"/><path class="hdwjuyb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:splitpro" /></template>
