<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl9btdb8y.css';
import '../../css/b/bf_6q8b-r.css';
import '../../css/h/hizge7bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yl9btdb8y"/><path class="bf_6q8b-r"/><path class="hizge7bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:suitcase-lines-bold" /></template>
