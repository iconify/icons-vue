<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elb1vsb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="elb1vsb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:scope" /></template>
