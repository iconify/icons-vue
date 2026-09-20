<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaiv5obsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uaiv5obsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-showering-with-soap-under-shower-spray" /></template>
