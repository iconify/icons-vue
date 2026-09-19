<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e56rnvsiz.css';
import '../../css/d/dqy3eyidd.css';
import '../../css/u/uh57q-l3l.css';
import '../../css/q/qiqxy6bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e56rnvsiz"/><path class="dqy3eyidd"/><path class="uh57q-l3l"/><path class="qiqxy6bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:trash" /></template>
