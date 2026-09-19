<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw_qod65h.css';
import '../../css/h/hyjd_db4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="aw_qod65h"/><path class="hyjd_db4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:se-4x3" /></template>
