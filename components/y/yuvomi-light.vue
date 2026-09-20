<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_6jlnb7u.css';
import '../../css/i/i66y37nvy.css';
import '../../css/u/usf_wsn7b.css';
import '../../css/a/a2ox3_bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g_6jlnb7u"/><circle class="i66y37nvy"/><circle class="usf_wsn7b"/><circle class="a2ox3_bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yuvomi-light" /></template>
