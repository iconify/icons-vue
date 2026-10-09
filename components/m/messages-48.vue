<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lre1b2w1l.css';
import '../../css/b/b7wt3uvay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lre1b2w1l"/><path class="b7wt3uvay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:messages-48" /></template>
