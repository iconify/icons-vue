<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq4vmr3hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="eq4vmr3hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:vote-yea" /></template>
