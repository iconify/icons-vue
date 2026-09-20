<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fru1dogiw.css';
import '../../css/l/ltqrw6w2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fru1dogiw"/><path class="ltqrw6w2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:sitar-16" /></template>
