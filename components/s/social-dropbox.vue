<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl_dgobdx.css';
import '../../css/v/vvtsvebww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="yl_dgobdx"/><path class="vvtsvebww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-dropbox" /></template>
