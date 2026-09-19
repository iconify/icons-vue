<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awwetebdu.css';
import '../../css/p/pyttu4r7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="awwetebdu"/><path clip-rule="evenodd" class="pyttu4r7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:nixos" /></template>
