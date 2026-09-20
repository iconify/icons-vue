<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puvxshblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="puvxshblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:parking-garage-11" /></template>
