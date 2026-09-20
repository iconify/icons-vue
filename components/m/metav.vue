<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss2xjkb3d.css';
import '../../css/n/n_iamfbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ss2xjkb3d"/><path class="n_iamfbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:metav" /></template>
