<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjdmveb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wjdmveb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:unlock-alt" /></template>
