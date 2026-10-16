<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opadiwbki.css';
import '../../css/y/yk_ojccds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="opadiwbki"/><path class="yk_ojccds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:subscript-20" /></template>
