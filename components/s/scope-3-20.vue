<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcck3kbsm.css';
import '../../css/o/o6lswx5rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zcck3kbsm"/><path class="o6lswx5rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scope-3-20" /></template>
