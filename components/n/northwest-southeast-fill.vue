<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ork6cbxuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ork6cbxuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:northwest-southeast-fill" /></template>
