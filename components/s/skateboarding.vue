<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy-bghb3k.css';
import '../../css/v/v8a8hebya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<ellipse class="sy-bghb3k"/><path class="v8a8hebya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:skateboarding" /></template>
