<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwvk4z-7p.css';
import '../../css/a/aa_03ls8j.css';
import '../../css/i/iki_14f2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kwvk4z-7p"/><rect class="aa_03ls8j"/><rect class="aa_03ls8j"/><path class="iki_14f2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:print-sharp" /></template>
