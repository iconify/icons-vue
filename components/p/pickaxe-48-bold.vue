<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjyqpubda.css';
import '../../css/n/niilcsy8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pjyqpubda"/><path class="niilcsy8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pickaxe-48-bold" /></template>
