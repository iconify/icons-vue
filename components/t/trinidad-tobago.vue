<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3qu93bwv.css';
import '../../css/w/wbb6ggb3t.css';
import '../../css/b/bhjcuuxbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="a3qu93bwv"/><path class="wbb6ggb3t"/><path class="bhjcuuxbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:trinidad-tobago" /></template>
