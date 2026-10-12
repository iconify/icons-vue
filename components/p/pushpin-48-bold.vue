<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7aw6lb_z.css';
import '../../css/b/b9njywbbk.css';
import '../../css/u/uyyqc0_4u.css';
import '../../css/t/tyapp0bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c7aw6lb_z"/><path class="b9njywbbk"/><path class="uyyqc0_4u"/><path class="tyapp0bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pushpin-48-bold" /></template>
