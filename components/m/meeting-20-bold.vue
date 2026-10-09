<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gihw2lrko.css';
import '../../css/b/brlnqubgb.css';
import '../../css/o/ougbzrbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gihw2lrko"/><path class="brlnqubgb"/><path class="ougbzrbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:meeting-20-bold" /></template>
