<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iohia0n9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iohia0n9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:wheelchair" /></template>
