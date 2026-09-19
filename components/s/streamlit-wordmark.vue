<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyp86db-i.css';
import '../../css/h/hrs2k7xqz.css';
import '../../css/v/v7ll8i85l.css';
import '../../css/a/a0xyf1bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zyp86db-i"/><path class="hrs2k7xqz"/><path class="v7ll8i85l"/><path class="a0xyf1bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:streamlit-wordmark" /></template>
