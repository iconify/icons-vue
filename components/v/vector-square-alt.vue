<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo664i1hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo664i1hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:vector-square-alt" /></template>
