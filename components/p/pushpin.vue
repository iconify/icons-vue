<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gae0srbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gae0srbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:pushpin" /></template>
