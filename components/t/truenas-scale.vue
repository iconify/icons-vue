<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5v3h_0wx.css';
import '../../css/h/ht7jy51cn.css';
import '../../css/w/w14eijbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x5v3h_0wx"/><path class="ht7jy51cn"/><path class="w14eijbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:truenas-scale" /></template>
