<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvtkyibzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvtkyibzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:panel-bottom" /></template>
