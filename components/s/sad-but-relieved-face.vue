<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw9z725_e.css';
import '../../css/l/llu4l5c-t.css';
import '../../css/d/dv5k-kbxm.css';
import '../../css/k/k9jsl_s7l.css';
import '../../css/i/i95m7f66s.css';
import '../../css/g/gitxq1b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="tw9z725_e"/><path class="llu4l5c-t"/><path class="dv5k-kbxm"/><path class="k9jsl_s7l"/><path class="i95m7f66s"/><path class="gitxq1b5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:sad-but-relieved-face" /></template>
