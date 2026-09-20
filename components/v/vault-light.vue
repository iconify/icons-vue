<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv2k8ptcj.css';
import '../../css/d/d9yuvfbmn.css';
import '../../css/z/z3fjvlb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv2k8ptcj"/><path class="d9yuvfbmn"/><path class="z3fjvlb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:vault-light" /></template>
