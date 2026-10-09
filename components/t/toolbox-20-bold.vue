<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvyjh5a_p.css';
import '../../css/g/g95ma61en.css';
import '../../css/s/s4i4qlbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hvyjh5a_p"/><path class="g95ma61en"/><path class="s4i4qlbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:toolbox-20-bold" /></template>
