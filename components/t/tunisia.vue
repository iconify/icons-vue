<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdftbpbaj.css';
import '../../css/w/wfcjrhbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="wdftbpbaj"/><path class="wfcjrhbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:tunisia" /></template>
