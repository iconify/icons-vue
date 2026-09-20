<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfstg2awc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zfstg2awc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sign-beside-car" /></template>
