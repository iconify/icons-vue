<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn86vr-5u.css';
import '../../css/h/hjs-1h8-e.css';
import '../../css/v/v4b84_btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gn86vr-5u"/><path class="hjs-1h8-e"/><path class="v4b84_btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:offset-48-bold" /></template>
