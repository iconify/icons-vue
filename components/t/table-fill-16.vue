<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjbvnem1g.css';
import '../../css/p/ppiwk-bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<rect class="qjbvnem1g"/><path class="ppiwk-bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:table-fill-16" /></template>
