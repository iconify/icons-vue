<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc5fb6b1r.css';
import '../../css/l/lix3kwe4f.css';
import '../../css/m/mmrx08g_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pc5fb6b1r"/><path class="lix3kwe4f"/><path class="mmrx08g_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:road" /></template>
