<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2mf5ebrq.css';
import '../../css/o/o_3md2c4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g2mf5ebrq"/><path class="o_3md2c4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:scilla" /></template>
