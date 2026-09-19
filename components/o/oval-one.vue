<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar01g9bbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="ar01g9bbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:oval-one" /></template>
