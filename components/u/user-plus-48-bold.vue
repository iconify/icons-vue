<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhffk1rfs.css';
import '../../css/w/wd6p9pbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jhffk1rfs"/><path class="wd6p9pbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-plus-48-bold" /></template>
