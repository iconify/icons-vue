<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1d2hbbbl.css';
import '../../css/t/to__--22z.css';
import '../../css/l/lzwt4-b9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t1d2hbbbl"/><path class="to__--22z"/><path class="lzwt4-b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:offshore-platform-20-bold" /></template>
