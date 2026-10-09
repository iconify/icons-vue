<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prrieubjn.css';
import '../../css/b/blb62kxgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="prrieubjn"/><path class="blb62kxgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:unlock-20" /></template>
