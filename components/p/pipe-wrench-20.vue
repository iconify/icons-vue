<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b20gz5bfs.css';
import '../../css/b/bv0gny4-m.css';
import '../../css/o/on0pidpto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b20gz5bfs"/><path class="bv0gny4-m"/><path class="on0pidpto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-wrench-20" /></template>
