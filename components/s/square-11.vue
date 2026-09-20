<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/octq69bdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="octq69bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:square-11" /></template>
