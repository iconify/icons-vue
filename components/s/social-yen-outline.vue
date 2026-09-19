<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb6ttobwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pb6ttobwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-yen-outline" /></template>
