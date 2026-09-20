<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjn-m4mbs.css';
import '../../css/y/yrit3k1ll.css';
import '../../css/j/jm-3xzqde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bjn-m4mbs"/><path class="yrit3k1ll"/><circle class="jm-3xzqde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rsshub" /></template>
