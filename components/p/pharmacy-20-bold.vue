<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4hf1bcaj.css';
import '../../css/b/b6bjo8bom.css';
import '../../css/a/ad_8r9xgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p4hf1bcaj"/><path class="b6bjo8bom"/><path class="ad_8r9xgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pharmacy-20-bold" /></template>
