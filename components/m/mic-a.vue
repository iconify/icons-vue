<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-lg0wb-p.css';
import '../../css/w/w7cn_ur_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b-lg0wb-p"/><path class="w7cn_ur_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:mic-a" /></template>
