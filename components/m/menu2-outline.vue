<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcumv1bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zcumv1bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:menu2-outline" /></template>
