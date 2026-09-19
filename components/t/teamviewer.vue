<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qut9t6lxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qut9t6lxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:teamviewer" /></template>
