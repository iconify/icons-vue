<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnlnjbcmb.css';
import '../../css/e/exdnk9b2b.css';
import '../../css/z/z1jg2ibea.css';
import '../../css/j/jiqf9lbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mnlnjbcmb"/><path class="exdnk9b2b"/><path class="z1jg2ibea"/><path class="jiqf9lbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:save-annotation" /></template>
