<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oov7omrot.css';
import '../../css/a/a7x1lr5rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oov7omrot"/><path class="a7x1lr5rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:state-of-charge-20" /></template>
