<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9s8gdcsr.css';
import '../../css/g/gs-juzbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9s8gdcsr"/><path clip-rule="evenodd" class="gs-juzbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:sand-watch-outline" /></template>
