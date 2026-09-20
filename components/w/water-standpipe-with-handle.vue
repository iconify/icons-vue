<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr54odb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gr54odb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:water-standpipe-with-handle" /></template>
