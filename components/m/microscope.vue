<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkooz0zfl.css';
import '../../css/z/za8l1lbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkooz0zfl"/><path class="za8l1lbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:microscope" /></template>
