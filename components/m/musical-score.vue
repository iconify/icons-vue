<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elac0jvzd.css';
import '../../css/p/p9v66kg_a.css';
import '../../css/a/a03h6bchc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="elac0jvzd"/><circle class="p9v66kg_a"/><circle class="a03h6bchc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:musical-score" /></template>
