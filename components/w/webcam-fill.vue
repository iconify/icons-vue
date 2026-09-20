<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoorgtbar.css';
import '../../css/k/ks42vwnso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoorgtbar"/><path clip-rule="evenodd" class="ks42vwnso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:webcam-fill" /></template>
