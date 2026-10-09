<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2ll1nb8o.css';
import '../../css/z/zl7g3rzgo.css';
import '../../css/b/bi4oaoona.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e2ll1nb8o"/><path class="zl7g3rzgo"/><path class="bi4oaoona"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:warehouse-20-bold" /></template>
