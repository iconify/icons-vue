<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxd5-pbku.css';
import '../../css/f/fblpe-b2f.css';
import '../../css/c/c65-ehvfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zxd5-pbku"/><path class="fblpe-b2f"/><path class="c65-ehvfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vertical-solar-48" /></template>
