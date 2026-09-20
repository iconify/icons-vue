<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2o_znbdb.css';
import '../../css/v/vh7rfhbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c2o_znbdb"/><path clip-rule="evenodd" class="vh7rfhbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:trash-full-16" /></template>
