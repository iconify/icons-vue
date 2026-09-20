<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf9w5nbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="gf9w5nbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:teahouse-11" /></template>
