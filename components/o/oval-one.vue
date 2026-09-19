<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahrb5lbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="ahrb5lbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:oval-one" /></template>
