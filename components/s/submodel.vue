<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1ou_2w2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z1ou_2w2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:submodel" /></template>
