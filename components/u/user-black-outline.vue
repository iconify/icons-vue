<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkuzuteuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bkuzuteuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:user-black-outline" /></template>
