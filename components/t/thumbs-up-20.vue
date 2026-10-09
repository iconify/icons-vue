<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy8iuubej.css';
import '../../css/y/yc11i_vei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sy8iuubej"/><path class="yc11i_vei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thumbs-up-20" /></template>
