<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt8szpbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wt8szpbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:virus-lab-research-test-tube" /></template>
