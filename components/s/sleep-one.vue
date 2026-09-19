<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofrod_8io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ofrod_8io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sleep-one" /></template>
