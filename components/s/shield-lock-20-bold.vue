<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld3dvsbdz.css';
import '../../css/p/pudna3b6q.css';
import '../../css/a/a-axxkxuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ld3dvsbdz"/><path class="pudna3b6q"/><path class="a-axxkxuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-lock-20-bold" /></template>
