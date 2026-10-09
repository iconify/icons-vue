<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8vhyqvci.css';
import '../../css/f/f8cnuqbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t8vhyqvci"/><path class="f8cnuqbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rotate-ccw-20" /></template>
