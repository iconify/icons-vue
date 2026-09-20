<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn3le97iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn3le97iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:xwiki" /></template>
