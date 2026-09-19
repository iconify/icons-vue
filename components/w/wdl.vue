<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rls1xqfjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":356,"height":512};
const content = `<path class="rls1xqfjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:wdl" /></template>
