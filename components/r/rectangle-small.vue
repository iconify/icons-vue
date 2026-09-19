<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpaos2b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lpaos2b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:rectangle-small" /></template>
