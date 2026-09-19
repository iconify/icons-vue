<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3uf27rlh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3uf27rlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:umbrella-alt-01" /></template>
