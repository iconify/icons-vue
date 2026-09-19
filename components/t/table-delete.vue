<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i38todi1o.css';
import '../../css/x/xv802vxka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i38todi1o"/><path class="xv802vxka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:table-delete" /></template>
