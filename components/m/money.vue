<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7j8ofo6z.css';
import '../../css/l/lf3nfothj.css';
import '../../css/z/zp_lnpb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r7j8ofo6z"/><path class="lf3nfothj"/><path class="zp_lnpb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:money" /></template>
