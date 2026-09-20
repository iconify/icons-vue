<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fprq_0fsn.css';
import '../../css/p/p__zjibpv.css';
import '../../css/z/zsuyb4b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fprq_0fsn"/><path class="p__zjibpv"/><path class="zsuyb4b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rosterhash" /></template>
