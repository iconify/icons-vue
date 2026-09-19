<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grs0l_bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grs0l_bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:math" /></template>
