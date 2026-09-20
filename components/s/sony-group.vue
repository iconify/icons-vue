<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyuwmlbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":263.352,"height":46.74};
const content = `<path class="jyuwmlbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sony-group" /></template>
