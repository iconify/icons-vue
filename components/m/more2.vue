<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1l3iv1qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1l3iv1qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:more2" /></template>
