<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj1g41blw.css';
import '../../css/l/lw6oj00xq.css';
import '../../css/s/sqitbfasi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="tj1g41blw"/><path class="lw6oj00xq"/><path class="sqitbfasi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:reunion" /></template>
