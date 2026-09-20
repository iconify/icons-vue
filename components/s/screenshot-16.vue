<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf0wplfja.css';
import '../../css/o/o9m46ebzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gf0wplfja"/><path clip-rule="evenodd" class="o9m46ebzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:screenshot-16" /></template>
