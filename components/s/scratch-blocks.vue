<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl87dzblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl87dzblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:scratch-blocks" /></template>
