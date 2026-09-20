<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf5ax2rgf.css';
import '../../css/r/r39nnteoa.css';
import '../../css/e/eog225bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rf5ax2rgf"/><path class="r39nnteoa"/><path class="eog225bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mediamanager-light" /></template>
