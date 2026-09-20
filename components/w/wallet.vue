<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dute4tn_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dute4tn_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:wallet" /></template>
