<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/f/fgf3lmnhv.css';
import '../../css/s/se9gb8bkp.css';
import '../../css/z/zagwpqb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fgf3lmnhv"/><path class="se9gb8bkp"/><path class="zagwpqb9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:quill-write-02" /></template>
