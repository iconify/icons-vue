<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcd41kb4g.css';
import '../../css/n/n7msz9oby.css';
import '../../css/a/axlgonxbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mcd41kb4g"/><path class="n7msz9oby"/><path class="axlgonxbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mooring-20" /></template>
