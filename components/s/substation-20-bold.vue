<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gikhi2gcs.css';
import '../../css/v/v10bzbf9m.css';
import '../../css/i/iw3d79bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gikhi2gcs"/><path class="v10bzbf9m"/><path class="iw3d79bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:substation-20-bold" /></template>
