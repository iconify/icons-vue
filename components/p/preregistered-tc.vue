<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2i40wv8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f2i40wv8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:preregistered-tc" /></template>
