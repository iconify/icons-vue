<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbhew13zs.css';
import '../../css/c/cbep2fbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jbhew13zs"/><path class="cbep2fbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:return-down-forward-sharp" /></template>
