<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j71d__mgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":283.46,"height":283.46};
const content = `<path class="j71d__mgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:photoprism-light" /></template>
