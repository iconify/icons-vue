<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c25225b7t.css';
import '../../css/c/cy89d844n.css';
import '../../css/c/cqgc1xk8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c25225b7t"/><path class="cy89d844n"/><path class="cqgc1xk8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:toolbox-48" /></template>
