<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzwebw3gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="jzwebw3gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:podcast" /></template>
