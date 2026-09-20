<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlttyjbjw.css';
import '../../css/y/ymagrdb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlttyjbjw"/><path class="ymagrdb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:some-share-ios" /></template>
