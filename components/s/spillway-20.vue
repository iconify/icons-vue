<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6xx492kn.css';
import '../../css/x/xlyqlub7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b6xx492kn"/><path class="xlyqlub7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spillway-20" /></template>
