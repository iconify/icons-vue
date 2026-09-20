<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b85kfggca.css';
import '../../css/d/dqv-n8bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b85kfggca"/><path class="dqv-n8bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:taze" /></template>
