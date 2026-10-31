<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv8upmbsd.css';
import '../../css/d/dv__-hbaw.css';
import '../../css/r/rkeykmpmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="gv8upmbsd"/><path class="dv__-hbaw"/><path class="rkeykmpmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:maldives" /></template>
