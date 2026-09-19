<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsfu-mu3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="rsfu-mu3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:pause-alt" /></template>
