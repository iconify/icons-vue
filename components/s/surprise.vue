<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciwwc7f0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="ciwwc7f0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:surprise" /></template>
