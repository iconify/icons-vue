<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l1s8gobzn.css';
import '../../css/b/b86buo32x.css';
import '../../css/k/ki55z6ilg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l1s8gobzn wm-a"/><path class="b86buo32x"/><path class="ki55z6ilg wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:unlock" /></template>
