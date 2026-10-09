<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdtvt3bkl.css';
import '../../css/b/bypdiev1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gdtvt3bkl"/><path class="bypdiev1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sailboat-48-bold" /></template>
