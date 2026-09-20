<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9qoumbuq.css';
import '../../css/q/qkol7euix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c9qoumbuq"/><path class="qkol7euix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wiredoor-light" /></template>
