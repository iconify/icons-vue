<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcw5r9b9i.css';
import '../../css/j/jtvessbvn.css';
import '../../css/o/oxb2pjboe.css';
import '../../css/b/bo1s8jdel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gcw5r9b9i"/><path class="jtvessbvn"/><path class="oxb2pjboe"/><path class="bo1s8jdel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:questions" /></template>
