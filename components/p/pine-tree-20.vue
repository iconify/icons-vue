<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix3tztiqy.css';
import '../../css/s/sg1__vokg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ix3tztiqy"/><path class="sg1__vokg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pine-tree-20" /></template>
