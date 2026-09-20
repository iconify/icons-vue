<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f32j-zrdv.css';
import '../../css/t/t_s3ty_ue.css';
import '../../css/f/f-nfbsbjy.css';
import '../../css/l/l7yuwkycl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f32j-zrdv"/><path class="t_s3ty_ue"/><path class="f-nfbsbjy"/><path class="l7yuwkycl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:tsil" /></template>
