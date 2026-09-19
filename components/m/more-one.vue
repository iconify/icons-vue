<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-a1t9yth.css';
import '../../css/m/mprl4mbnb.css';
import '../../css/c/chpyfs2is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="c-a1t9yth"/><circle class="mprl4mbnb"/><circle class="chpyfs2is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:more-one" /></template>
