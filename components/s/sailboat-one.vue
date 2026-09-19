<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z35tf_spx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z35tf_spx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sailboat-one" /></template>
