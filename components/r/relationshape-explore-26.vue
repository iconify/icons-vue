<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni5gklkjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="ni5gklkjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:relationshape-explore-26" /></template>
