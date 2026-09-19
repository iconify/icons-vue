<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbxjejj-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":24};
const content = `<path class="jbxjejj-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:paw" /></template>
