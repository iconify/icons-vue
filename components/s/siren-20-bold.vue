<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-0g-v3zq.css';
import '../../css/l/lnh0e5bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z-0g-v3zq"/><path class="lnh0e5bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:siren-20-bold" /></template>
