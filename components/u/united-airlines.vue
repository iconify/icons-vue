<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxicmkb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxicmkb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:united-airlines" /></template>
