<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcl10mxau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcl10mxau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:softpedia" /></template>
