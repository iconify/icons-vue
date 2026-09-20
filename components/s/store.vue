<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5ersu14l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="b5ersu14l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:store" /></template>
