<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfg1m8b6f.css';
import '../../css/w/wtom3hs6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jfg1m8b6f"/><path class="wtom3hs6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:picnic-20-bold" /></template>
