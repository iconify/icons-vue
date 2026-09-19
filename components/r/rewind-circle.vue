<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwibdw4bb.css';
import '../../css/a/akf245-tr.css';
import '../../css/n/nzv-jwb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwibdw4bb"/><path class="akf245-tr"/><path class="nzv-jwb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rewind-circle" /></template>
