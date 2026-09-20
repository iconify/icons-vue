<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sib2qlbqm.css';
import '../../css/o/o2vbwlbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sib2qlbqm"/><path clip-rule="evenodd" class="o2vbwlbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:spam-32" /></template>
