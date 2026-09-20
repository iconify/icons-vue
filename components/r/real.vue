<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iupyxnbgc.css';
import '../../css/m/mabwzbbvc.css';
import '../../css/c/cj8-pez3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iupyxnbgc"/><path class="mabwzbbvc"/><path class="cj8-pez3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:real" /></template>
