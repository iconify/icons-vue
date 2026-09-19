<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjlu84bvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="kjlu84bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:mintbit" /></template>
