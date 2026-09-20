<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt0lgbd7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="qt0lgbd7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:snowmobile" /></template>
