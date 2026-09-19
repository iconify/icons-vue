<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjo6bv0or.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":443,"height":512};
const content = `<path class="qjo6bv0or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:sequelize" /></template>
