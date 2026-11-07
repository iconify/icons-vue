<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm03gzbnp.css';
import '../../css/j/j60t8hb-x.css';
import '../../css/d/d0gfj5yqu.css';
import '../../css/s/sl1flzbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="j60t8hb-x"/><path class="d0gfj5yqu"/><path class="sl1flzbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:soundwave-square-bold-duotone" /></template>
