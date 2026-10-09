<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgcb4c_nz.css';
import '../../css/c/ctkosrb3v.css';
import '../../css/l/lxsqj045t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jgcb4c_nz"/><path class="ctkosrb3v"/><path class="lxsqj045t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-lock-20-bold" /></template>
