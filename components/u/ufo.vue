<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6k-cw5wu.css';
import '../../css/e/eppqdoeru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6k-cw5wu"/><path class="eppqdoeru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ufo" /></template>
