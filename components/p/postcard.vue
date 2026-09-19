<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paaeio2fp.css';
import '../../css/r/rx4b74v7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="paaeio2fp"/><path class="rx4b74v7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:postcard" /></template>
