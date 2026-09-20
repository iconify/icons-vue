<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq5wtgblw.css';
import '../../css/c/cxplgm_hu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq5wtgblw"/><path clip-rule="evenodd" class="cxplgm_hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:obvious" /></template>
