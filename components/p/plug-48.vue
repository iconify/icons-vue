<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haxjj3y8l.css';
import '../../css/c/ca098sbgi.css';
import '../../css/p/pbj3dmu5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="haxjj3y8l"/><path class="ca098sbgi"/><path class="pbj3dmu5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plug-48" /></template>
