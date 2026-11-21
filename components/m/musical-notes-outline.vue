<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_5qwt2go.css';
import '../../css/o/o9mqkzbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b_5qwt2go"/><path class="o9mqkzbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:musical-notes-outline" /></template>
