<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqc5wb6qw.css';
import '../../css/s/s4umu5bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mqc5wb6qw"/><path class="s4umu5bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:radiator-20-bold" /></template>
