<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osc_bo0fp.css';
import '../../css/g/gxfstbt8c.css';
import '../../css/a/at5734fty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="osc_bo0fp"/><path class="gxfstbt8c"/><path class="at5734fty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:villa-20" /></template>
