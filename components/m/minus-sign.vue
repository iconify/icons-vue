<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj9892bvm.css';
import '../../css/w/wo110wbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="tj9892bvm"/><path class="wo110wbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:minus-sign" /></template>
