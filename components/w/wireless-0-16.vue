<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyjr-7brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pyjr-7brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:wireless-0-16" /></template>
