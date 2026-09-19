<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-_mhjbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d-_mhjbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:sonos" /></template>
