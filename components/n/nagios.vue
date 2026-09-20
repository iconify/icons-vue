<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd3noewjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":51.89,"height":64,"left":4.66,"top":-1.4};
const content = `<path class="wd3noewjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nagios" /></template>
