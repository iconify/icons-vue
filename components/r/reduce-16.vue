<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv5ee7d2i.css';
import '../../css/j/jdm0z2b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lv5ee7d2i"/><path class="jdm0z2b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:reduce-16" /></template>
