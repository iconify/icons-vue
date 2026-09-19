<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htgbsacnp.css';
import '../../css/y/ypfktcc0d.css';
import '../../css/d/dd9yyy66g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="htgbsacnp"/><path class="ypfktcc0d"/><path class="dd9yyy66g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:news" /></template>
