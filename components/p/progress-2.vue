<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjoc32bjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="zjoc32bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:progress-2" /></template>
