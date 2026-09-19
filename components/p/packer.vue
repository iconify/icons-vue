<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxqj9naah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pxqj9naah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:packer" /></template>
