<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvqm_db9h.css';
import '../../css/h/hd2zslizq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cvqm_db9h"/><path class="hd2zslizq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:openfilefolder" /></template>
