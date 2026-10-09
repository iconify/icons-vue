<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otb2xbb3k.css';
import '../../css/p/pkdwskbpr.css';
import '../../css/g/g1mzogb6g.css';
import '../../css/d/da0i6bcpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="otb2xbb3k"/><path class="pkdwskbpr"/><path class="g1mzogb6g"/><path class="da0i6bcpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:recycle-48-bold" /></template>
