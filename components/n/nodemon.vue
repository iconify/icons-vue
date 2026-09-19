<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofnqojbtj.css';
import '../../css/n/nrfjz124s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ofnqojbtj"/><path class="nrfjz124s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nodemon" /></template>
