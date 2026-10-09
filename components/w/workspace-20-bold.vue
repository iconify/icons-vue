<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3-qndq9t.css';
import '../../css/h/hm6x3kk-j.css';
import '../../css/h/hl3yc9npn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a3-qndq9t"/><path class="hm6x3kk-j"/><path class="hl3yc9npn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:workspace-20-bold" /></template>
