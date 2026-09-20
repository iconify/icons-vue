<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq7cyxzqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gq7cyxzqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-standing-with-droplets" /></template>
