<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egmmgub_l.css';
import '../../css/u/u1hnyj58h.css';
import '../../css/b/b5hlbebng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="egmmgub_l"/><path class="u1hnyj58h"/><path class="b5hlbebng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:time-of-use-20-bold" /></template>
