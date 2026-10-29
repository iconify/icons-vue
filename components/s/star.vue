<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bckmiy40m.css';
import '../../css/h/hd6dabc8y.css';
import '../../css/j/jubvaetez.css';
import '../../css/r/rdcb-9b_c.css';
import '../../css/v/v86l0ib4h.css';
import '../../css/o/o0zupef1x.css';
import '../../css/t/txc_fubpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bckmiy40m wm-shadow"/><path class="hd6dabc8y wm-k"/><path class="jubvaetez wm-k"/><path class="rdcb-9b_c wm-k"/><path class="v86l0ib4h wm-k"/><path class="o0zupef1x wm-k"/><path class="txc_fubpw wm-shine"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:star" /></template>
