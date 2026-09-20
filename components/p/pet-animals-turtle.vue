<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjmg4z__o.css';
import '../../css/d/d1jue8bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sjmg4z__o"/><path class="d1jue8bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:pet-animals-turtle" /></template>
