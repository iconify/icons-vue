<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3vembbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":326,"height":671};
const content = `<path class="t3vembbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:s" /></template>
