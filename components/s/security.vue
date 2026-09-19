<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rulstbbgo.css';
import '../../css/c/c3te-ab8q.css';
import '../../css/x/x35msp2lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rulstbbgo"/><path class="c3te-ab8q"/><path class="x35msp2lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:security" /></template>
