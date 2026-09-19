<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtzgfvdyl.css';
import '../../css/j/jqvrv4bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wtzgfvdyl"/><path class="jqvrv4bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:translation-created-fill-12" /></template>
